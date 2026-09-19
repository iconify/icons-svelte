<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmeo3k1fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hmeo3k1fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube-transparent-solid" {...props}></Icon>
