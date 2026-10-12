<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta5f1hbwd.css';
import '../../css/u/une-91bkz.css';
import '../../css/g/gk5hfuifs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ta5f1hbwd"/><path class="une-91bkz"/><path class="gk5hfuifs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladybird-48-bold" {...props}></Icon>
