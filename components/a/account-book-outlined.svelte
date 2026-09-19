<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqov4sbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kqov4sbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:account-book-outlined" {...props}></Icon>
