<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nayh5bbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nayh5bbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:paper-airplane" {...props}></Icon>
