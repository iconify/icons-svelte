<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jur25dbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jur25dbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:folder-fill" {...props}></Icon>
