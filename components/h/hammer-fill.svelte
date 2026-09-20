<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7y4svbea.css';
import '../../css/o/o2549tb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7y4svbea"/><path class="o2549tb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hammer-fill" {...props}></Icon>
