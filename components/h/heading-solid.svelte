<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j32zss-kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j32zss-kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heading-solid" {...props}></Icon>
