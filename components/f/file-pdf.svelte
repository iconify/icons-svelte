<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/updz07b-a.css';
import '../../css/g/g8ph7i0bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="updz07b-a"/><path class="g8ph7i0bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-pdf" {...props}></Icon>
