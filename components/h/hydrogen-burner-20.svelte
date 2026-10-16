<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o63iyfbss.css';
import '../../css/t/tmavxu-df.css';
import '../../css/u/u7fpslg-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o63iyfbss"/><path class="tmavxu-df"/><path class="u7fpslg-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-burner-20" {...props}></Icon>
