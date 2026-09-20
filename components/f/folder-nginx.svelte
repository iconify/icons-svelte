<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcy98sbxp.css';
import '../../css/q/q6t1v8bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kcy98sbxp"/><path class="q6t1v8bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-nginx" {...props}></Icon>
