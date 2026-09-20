<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bich7zbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bich7zbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:barcode" {...props}></Icon>
