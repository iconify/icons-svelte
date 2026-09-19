<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csyah5ukg.css';
import '../../css/o/ou22v7n3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csyah5ukg"/><path class="ou22v7n3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrowhead-up-fill" {...props}></Icon>
