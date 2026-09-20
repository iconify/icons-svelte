<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6znz95qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6znz95qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:align-right" {...props}></Icon>
