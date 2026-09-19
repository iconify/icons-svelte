<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et74su9kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="et74su9kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:delete-row-outlined" {...props}></Icon>
