<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or5g61b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="or5g61b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:carry-out-fill" {...props}></Icon>
