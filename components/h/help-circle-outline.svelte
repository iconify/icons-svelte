<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr_xxwbkp.css';
import '../../css/d/dzrft4xru.css';
import '../../css/g/g47gadbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lr_xxwbkp"/><path class="dzrft4xru"/><circle class="g47gadbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:help-circle-outline" {...props}></Icon>
