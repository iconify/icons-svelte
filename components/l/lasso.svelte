<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml5jf-drw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml5jf-drw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lasso" {...props}></Icon>
