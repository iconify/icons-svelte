<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-td7-p-y.css';
import '../../css/h/hhhxw4j6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-td7-p-y"/><path class="hhhxw4j6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-storybook-open" {...props}></Icon>
