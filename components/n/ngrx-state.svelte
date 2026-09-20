<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6_1r758o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="w6_1r758o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ngrx-state" {...props}></Icon>
