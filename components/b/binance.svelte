<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezeyjpbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezeyjpbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:binance" {...props}></Icon>
