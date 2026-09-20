<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3rifrbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="k3rifrbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ngrx-entity" {...props}></Icon>
