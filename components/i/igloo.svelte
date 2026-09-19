<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6xqsjb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="o6xqsjb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:igloo" {...props}></Icon>
