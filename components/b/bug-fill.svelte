<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbvjsy3py.css';
import '../../css/i/iun2kcife.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tbvjsy3py"/><path class="iun2kcife"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bug-fill" {...props}></Icon>
