<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9dt8sqd.css';
import '../../css/g/gqp5qc1jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vi9dt8sqd"/><path class="gqp5qc1jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-claude-open" {...props}></Icon>
