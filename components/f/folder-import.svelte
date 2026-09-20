<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj5g77b1a.css';
import '../../css/z/z63mtn1lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tj5g77b1a"/><path class="z63mtn1lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-import" {...props}></Icon>
