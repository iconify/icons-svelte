<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf1fo6loa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf1fo6loa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:plus-square" {...props}></Icon>
