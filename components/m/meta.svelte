<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaa_3geeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iaa_3geeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:meta" {...props}></Icon>
