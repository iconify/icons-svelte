<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd153t_sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd153t_sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:layout-remove" {...props}></Icon>
