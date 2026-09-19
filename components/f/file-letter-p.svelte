<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h938hxb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h938hxb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:file-letter-p" {...props}></Icon>
