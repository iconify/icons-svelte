<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1pyb518k.css';
import '../../css/b/bavhjmbgw.css';
import '../../css/k/kruzn2_tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b1pyb518k"/><path class="bavhjmbgw"/><path class="kruzn2_tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:money-exchange" {...props}></Icon>
