<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al0fg069v.css';
import '../../css/x/x1_ejpb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al0fg069v"/><path class="x1_ejpb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hjson" {...props}></Icon>
