<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ft_mbie.css';
import '../../css/l/lznd2ybdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n7ft_mbie"/><path class="lznd2ybdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-hat-48-bold" {...props}></Icon>
