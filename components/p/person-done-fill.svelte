<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvc5-zbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvc5-zbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-done-fill" {...props}></Icon>
