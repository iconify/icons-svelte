<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp_e8dmbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hp_e8dmbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-chat" {...props}></Icon>
