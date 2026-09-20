<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyx3e6b3g.css';
import '../../css/w/wnjmof43i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyx3e6b3g"/><path class="wnjmof43i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:folder-add-bold" {...props}></Icon>
