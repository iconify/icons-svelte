<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go71j8bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":311,"height":512};
const content = `<path class="go71j8bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mirah" {...props}></Icon>
