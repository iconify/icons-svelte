<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjcbaabfa.css';
import '../../css/c/cgwih5znj.css';
import '../../css/c/cl_ajub-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zjcbaabfa"/><path class="cgwih5znj"/><path class="cl_ajub-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-backup-open" {...props}></Icon>
