<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9xdadbxa.css';
import '../../css/z/zzudz-b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9xdadbxa"/><path class="zzudz-b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:motor-symbol-20" {...props}></Icon>
