<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgf-28bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hgf-28bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-alert-fill" {...props}></Icon>
