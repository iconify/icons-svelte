<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zat6rqfwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zat6rqfwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlequora" {...props}></Icon>
