<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv842m9yr.css';
import '../../css/r/rv_tlwbie.css';
import '../../css/s/s9cmspn9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yv842m9yr"/><path class="rv_tlwbie"/><path class="s9cmspn9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:canal-lock-20-bold" {...props}></Icon>
