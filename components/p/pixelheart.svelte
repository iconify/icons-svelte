<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uktpivbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="uktpivbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelheart" {...props}></Icon>
