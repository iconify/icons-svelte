<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itx6mhbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itx6mhbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-up-right-fill" {...props}></Icon>
