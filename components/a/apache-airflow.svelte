<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkk-kyy9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qkk-kyy9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:apache-airflow" {...props}></Icon>
