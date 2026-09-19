<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aku9edhek.css';
import '../../css/i/il_8vobti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aku9edhek"/><path class="il_8vobti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chess" {...props}></Icon>
