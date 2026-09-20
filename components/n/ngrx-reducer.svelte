<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2e0vabgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="q2e0vabgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ngrx-reducer" {...props}></Icon>
