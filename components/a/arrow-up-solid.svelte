<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd5m64cqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd5m64cqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-solid" {...props}></Icon>
