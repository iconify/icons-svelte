<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb3enpccq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nb3enpccq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:clear" {...props}></Icon>
