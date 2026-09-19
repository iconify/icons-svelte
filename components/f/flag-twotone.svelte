<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7yvrsswf.css';
import '../../css/t/t8radzbpg.css';
import '../../css/w/wmkeibccw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k7yvrsswf"/><path class="t8radzbpg"/><path class="wmkeibccw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:flag-twotone" {...props}></Icon>
