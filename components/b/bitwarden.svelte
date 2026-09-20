<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quiv4pbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quiv4pbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bitwarden" {...props}></Icon>
