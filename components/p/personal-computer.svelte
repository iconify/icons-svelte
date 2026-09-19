<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad7wxxbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad7wxxbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:personal-computer" {...props}></Icon>
