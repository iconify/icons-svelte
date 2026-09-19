<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p48dyi2lt.css';
import '../../css/e/emos5l7br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p48dyi2lt"/><path class="emos5l7br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:check-square" {...props}></Icon>
