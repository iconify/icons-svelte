<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egaei1gbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egaei1gbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:chevrolet" {...props}></Icon>
