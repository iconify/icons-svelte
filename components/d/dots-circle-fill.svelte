<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viud3_gtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viud3_gtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dots-circle-fill" {...props}></Icon>
