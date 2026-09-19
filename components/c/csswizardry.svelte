<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb025pbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kb025pbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:csswizardry" {...props}></Icon>
