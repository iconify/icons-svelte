<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8h3kyc4w.css';
import '../../css/u/u8acicc4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8h3kyc4w"/><path clip-rule="evenodd" class="u8acicc4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:info-24" {...props}></Icon>
