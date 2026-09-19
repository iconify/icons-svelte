<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oui3apb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oui3apb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:insert-row-below" {...props}></Icon>
