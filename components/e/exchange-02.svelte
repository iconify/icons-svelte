<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgcy-jbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgcy-jbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:exchange-02" {...props}></Icon>
