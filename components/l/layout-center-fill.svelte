<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh3i-6oef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh3i-6oef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-center-fill" {...props}></Icon>
