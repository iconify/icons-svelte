<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6mmyob4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6mmyob4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:chevrolet" {...props}></Icon>
