<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esqfgjb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esqfgjb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:menu-alt-02" {...props}></Icon>
