<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y01l-xu0e.css';
import '../../css/d/dzfzn_bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y01l-xu0e"/><path class="dzfzn_bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:lime" {...props}></Icon>
