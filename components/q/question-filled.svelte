<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guw_mk73j.css';
import '../../css/i/ilmsi6bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guw_mk73j"/><path clip-rule="evenodd" class="ilmsi6bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:question-filled" {...props}></Icon>
