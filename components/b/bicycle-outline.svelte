<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ap423kz.css';
import '../../css/v/vwjfqbcke.css';
import '../../css/o/o6u87gbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9ap423kz"/><path class="vwjfqbcke"/><path class="o6u87gbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:bicycle-outline" {...props}></Icon>
