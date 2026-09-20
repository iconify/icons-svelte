<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyjgdbcao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyjgdbcao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:gift-fill" {...props}></Icon>
