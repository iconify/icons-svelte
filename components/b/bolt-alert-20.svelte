<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9dzyiszx.css';
import '../../css/q/qz4brhaoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9dzyiszx"/><path class="qz4brhaoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-alert-20" {...props}></Icon>
