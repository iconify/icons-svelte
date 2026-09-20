<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prl8l2bvy.css';
import '../../css/p/ptfrs5bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="prl8l2bvy"/><path class="ptfrs5bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-trigger-open" {...props}></Icon>
