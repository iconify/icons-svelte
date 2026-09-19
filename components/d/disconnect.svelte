<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpaff3kmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lpaff3kmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:disconnect" {...props}></Icon>
