<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3eqq92lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3eqq92lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:person-delete-fill" {...props}></Icon>
