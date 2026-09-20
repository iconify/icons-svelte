<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjgthrqxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjgthrqxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:electronbuilder" {...props}></Icon>
