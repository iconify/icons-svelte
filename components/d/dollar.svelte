<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtvztsq6v.css';
import '../../css/v/v-s_jsdhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtvztsq6v"/><path class="v-s_jsdhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:dollar" {...props}></Icon>
