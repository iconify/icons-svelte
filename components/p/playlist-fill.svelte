<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5tb48bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5tb48bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:playlist-fill" {...props}></Icon>
