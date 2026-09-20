<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltow3qbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":413,"height":413,"left":-78.5};
const content = `<path class="ltow3qbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-kafka-dark" {...props}></Icon>
