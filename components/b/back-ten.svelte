<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftu5u0jmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftu5u0jmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:back-ten" {...props}></Icon>
