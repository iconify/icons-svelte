<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue7ba3bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="ue7ba3bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:home-option" {...props}></Icon>
