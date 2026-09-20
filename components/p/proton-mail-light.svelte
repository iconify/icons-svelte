<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knod1mnja.css';
import '../../css/f/f8da0bkqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knod1mnja"/><path class="f8da0bkqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-mail-light" {...props}></Icon>
