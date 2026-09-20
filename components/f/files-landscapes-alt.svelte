<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9q54j4jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9q54j4jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:files-landscapes-alt" {...props}></Icon>
