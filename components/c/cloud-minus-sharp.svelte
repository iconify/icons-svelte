<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efrn45bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efrn45bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-minus-sharp" {...props}></Icon>
