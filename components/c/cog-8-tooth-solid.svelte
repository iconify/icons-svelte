<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agu67jb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="agu67jb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cog-8-tooth-solid" {...props}></Icon>
