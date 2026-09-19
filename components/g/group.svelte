<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h66-yoa9l.css';
import '../../css/w/w-bvnpfvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h66-yoa9l"/><path class="w-bvnpfvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:group" {...props}></Icon>
