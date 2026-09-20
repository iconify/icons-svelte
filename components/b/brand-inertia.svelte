<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6eqh_5vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6eqh_5vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-inertia" {...props}></Icon>
