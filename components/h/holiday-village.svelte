<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2rc8bbax.css';
import '../../css/s/skkebdnpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="z2rc8bbax"/><path class="skkebdnpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:holiday-village" {...props}></Icon>
