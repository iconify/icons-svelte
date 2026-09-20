<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqp03tuhu.css';
import '../../css/h/htn9lvbbo.css';
import '../../css/f/fbzxk2bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="lqp03tuhu"/><path class="htn9lvbbo"/><path class="fbzxk2bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:list-favourite" {...props}></Icon>
