<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugm1pccgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ugm1pccgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:phidata" {...props}></Icon>
