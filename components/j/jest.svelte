<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idsx4vb9j.css';
import '../../css/l/li7u4ccwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":283};
const content = `<path class="idsx4vb9j"/><path class="li7u4ccwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jest" {...props}></Icon>
