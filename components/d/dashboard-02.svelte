<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqg2si9cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg2si9cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dashboard-02" {...props}></Icon>
