<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":293};
const content = `<path class="z9u1asblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:dovetail-icon" {...props}></Icon>
<style>
:global(.z9u1asblt) {
  fill: var(--svg-color--230078, #230078);
  d: path("m256 182.857l-64 36.572v-73.143l-64-36.974l64-36.17l64 36.572zm-128.01-73.143l-64 36.572V73.143L0 36.57L64 0l63.99 36.571zm0 146.286l-64 36.571l.01-73.142l-64-36.572l63.99-36.571l64 36.571z");
}

</style>
