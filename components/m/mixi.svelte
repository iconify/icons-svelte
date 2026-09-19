<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-_hd0b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v-_hd0b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:mixi" {...props}></Icon>
