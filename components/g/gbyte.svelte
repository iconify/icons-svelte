<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op3huwehw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op3huwehw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gbyte" {...props}></Icon>
