<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihh0_dbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihh0_dbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ejabberd-dark" {...props}></Icon>
