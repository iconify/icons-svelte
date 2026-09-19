<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enmtaibbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enmtaibbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:configure" {...props}></Icon>
