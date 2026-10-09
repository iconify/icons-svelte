<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwaplabmu.css';
import '../../css/o/o-xjgxbux.css';
import '../../css/y/yl2ujob7n.css';
import '../../css/z/z65fwkbap.css';
import '../../css/d/djjvp7y2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwaplabmu"/><path class="o-xjgxbux"/><path class="yl2ujob7n"/><path class="z65fwkbap"/><path class="djjvp7y2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-handover-20" {...props}></Icon>
