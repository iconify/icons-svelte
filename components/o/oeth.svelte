<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc111xaga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc111xaga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:oeth" {...props}></Icon>
