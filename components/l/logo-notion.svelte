<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru7ki0x_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ru7ki0x_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-notion" {...props}></Icon>
