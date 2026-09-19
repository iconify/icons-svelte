<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoix4ob1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uoix4ob1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:equal-square" {...props}></Icon>
