<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c80kiybsf.css';
import '../../css/i/ib6qaybse.css';
import '../../css/e/efa1bkb1o.css';
import '../../css/d/dntz9tmey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c80kiybsf"/><path class="ib6qaybse"/><path class="efa1bkb1o"/><path class="dntz9tmey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-outline" {...props}></Icon>
