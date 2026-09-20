<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfeh66bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qfeh66bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:food" {...props}></Icon>
