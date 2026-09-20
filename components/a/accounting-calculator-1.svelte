<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be-3lv5bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be-3lv5bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:accounting-calculator-1" {...props}></Icon>
