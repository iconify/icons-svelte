<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9y8i63tx.css';
import '../../css/j/jor-usn7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9y8i63tx"/><path class="jor-usn7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-right-square" {...props}></Icon>
