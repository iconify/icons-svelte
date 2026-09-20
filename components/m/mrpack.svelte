<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx-_ic5tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":514,"height":514};
const content = `<path class="sx-_ic5tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:mrpack" {...props}></Icon>
