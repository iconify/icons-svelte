<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz-trqb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz-trqb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gitlab-fill-24" {...props}></Icon>
