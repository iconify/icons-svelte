<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq1-gqaos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq1-gqaos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:edit-pencil-02" {...props}></Icon>
