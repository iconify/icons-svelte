<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_wt5ub2x.css';
import '../../css/n/n1xy6nh9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_wt5ub2x"/><circle class="n1xy6nh9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:abstract-instance-outlined" {...props}></Icon>
